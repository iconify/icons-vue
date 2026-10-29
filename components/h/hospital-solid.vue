<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kffe7kb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kffe7kb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hospital-solid" /></template>
