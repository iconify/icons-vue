<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq_frzb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wq_frzb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-power-filled" /></template>
