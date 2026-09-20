<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flviq_1lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="flviq_1lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:helicopter" /></template>
