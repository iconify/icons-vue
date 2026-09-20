<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg5aw4bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg5aw4bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:arrow-down-circle" /></template>
