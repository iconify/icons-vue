<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geiclm85t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="geiclm85t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:flag" /></template>
