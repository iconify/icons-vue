<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h69cov3va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h69cov3va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-waterdrops-outline" /></template>
