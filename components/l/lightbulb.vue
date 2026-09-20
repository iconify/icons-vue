<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq3s8zbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq3s8zbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:lightbulb" /></template>
