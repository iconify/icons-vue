<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s17-xn6bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s17-xn6bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:history" /></template>
