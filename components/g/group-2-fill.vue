<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl_qbjujm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl_qbjujm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:group-2-fill" /></template>
