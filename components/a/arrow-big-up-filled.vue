<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot6xdwbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot6xdwbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:arrow-big-up-filled" /></template>
