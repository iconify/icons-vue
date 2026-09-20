<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn45hr9iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn45hr9iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-lock-outline" /></template>
