<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_4_vvxgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_4_vvxgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-3-line" /></template>
