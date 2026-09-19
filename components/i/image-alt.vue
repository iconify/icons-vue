<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu56ptb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu56ptb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:image-alt" /></template>
