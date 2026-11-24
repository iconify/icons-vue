<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cltq9j6ti.css';
import '../../css/q/qfntjihwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cltq9j6ti"/><path class="qfntjihwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-backup-filled" /></template>
