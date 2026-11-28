<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz24a0bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz24a0bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cookie-x" /></template>
