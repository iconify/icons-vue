<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvzf_gblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gvzf_gblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:magnet" /></template>
