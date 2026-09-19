<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9r1unb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="a9r1unb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:apple-pay" /></template>
