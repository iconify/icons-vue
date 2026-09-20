<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq48p7xon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq48p7xon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-sync-2" /></template>
