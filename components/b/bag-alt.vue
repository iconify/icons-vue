<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjpi7urvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjpi7urvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bag-alt" /></template>
