<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib2oze94a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib2oze94a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bell-ring-filled" /></template>
