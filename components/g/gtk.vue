<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxd_wxvqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxd_wxvqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:gtk" /></template>
