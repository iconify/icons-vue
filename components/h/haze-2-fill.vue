<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm2l9yb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm2l9yb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:haze-2-fill" /></template>
