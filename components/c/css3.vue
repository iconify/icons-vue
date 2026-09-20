<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we5ld5buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="we5ld5buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:css3" /></template>
