<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojsrhkbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ojsrhkbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:facebook-rect" /></template>
