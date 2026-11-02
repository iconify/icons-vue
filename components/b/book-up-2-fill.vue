<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzd2uob7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzd2uob7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-up-2-fill" /></template>
