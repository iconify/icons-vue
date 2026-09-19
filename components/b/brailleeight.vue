<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_akeuekh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="x_akeuekh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brailleeight" /></template>
