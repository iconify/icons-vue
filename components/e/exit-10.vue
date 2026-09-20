<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq35ehzop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="wq35ehzop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:exit-10" /></template>
