<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvs3lxber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvs3lxber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-2-line" /></template>
