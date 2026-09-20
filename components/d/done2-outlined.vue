<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k926z6j4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k926z6j4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:done2-outlined" /></template>
