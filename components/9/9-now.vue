<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq5pa6f5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq5pa6f5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:9-now" /></template>
