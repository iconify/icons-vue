<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku24kpydw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ku24kpydw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:heart" /></template>
