<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsg-22bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zsg-22bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:apacheignite-wordmark" /></template>
