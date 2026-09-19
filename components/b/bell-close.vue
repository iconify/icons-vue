<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvquftbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvquftbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:bell-close" /></template>
