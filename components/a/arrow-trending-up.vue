<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayhd7rbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayhd7rbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-trending-up" /></template>
