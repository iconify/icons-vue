<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-v6ilq_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-v6ilq_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kitchen-tap-off" /></template>
