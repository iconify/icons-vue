<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpja5bb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpja5bb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bitcoin" /></template>
