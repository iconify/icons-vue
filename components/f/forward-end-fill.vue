<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kja92kcsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kja92kcsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forward-end-fill" /></template>
