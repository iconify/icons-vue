<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbih5wbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mbih5wbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:dollar" /></template>
