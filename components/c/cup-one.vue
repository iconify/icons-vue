<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-hb33v6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c-hb33v6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cup-one" /></template>
