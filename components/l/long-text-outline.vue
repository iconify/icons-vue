<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc8_0qt7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc8_0qt7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:long-text-outline" /></template>
