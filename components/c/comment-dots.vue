<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpjz01dis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpjz01dis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:comment-dots" /></template>
