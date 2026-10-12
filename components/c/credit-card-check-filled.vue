<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eke7tccoi.css';
import '../../css/p/p8coosbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eke7tccoi"/><path class="p8coosbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:credit-card-check-filled" /></template>
