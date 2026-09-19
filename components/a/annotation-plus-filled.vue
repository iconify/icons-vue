<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrz2ljobp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrz2ljobp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:annotation-plus-filled" /></template>
