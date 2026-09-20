<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu1d4drrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu1d4drrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:livechat" /></template>
