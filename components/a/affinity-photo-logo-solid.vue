<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3b_m5t_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3b_m5t_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:affinity-photo-logo-solid" /></template>
