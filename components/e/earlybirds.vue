<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7w8ann-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="n7w8ann-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:earlybirds" /></template>
