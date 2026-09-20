<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_e47cbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_e47cbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:grid" /></template>
