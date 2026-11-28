<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzz7np1_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzz7np1_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cat-heart" /></template>
