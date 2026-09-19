<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgak4ob9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="cgak4ob9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:kakaotalk-square" /></template>
