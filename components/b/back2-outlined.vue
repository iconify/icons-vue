<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s88nnip0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s88nnip0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:back2-outlined" /></template>
