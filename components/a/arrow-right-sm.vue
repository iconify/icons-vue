<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2j401b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2j401b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-right-sm" /></template>
