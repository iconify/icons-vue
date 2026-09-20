<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8ppo7h5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n8ppo7h5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:block" /></template>
