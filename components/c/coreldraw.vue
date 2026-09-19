<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4epeyb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="t4epeyb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:coreldraw" /></template>
