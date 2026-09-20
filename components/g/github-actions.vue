<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxsdd63jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxsdd63jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:github-actions" /></template>
