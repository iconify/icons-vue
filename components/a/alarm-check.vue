<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsomaxd5w.css';
import '../../css/s/sc_o8zb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsomaxd5w"/><path class="sc_o8zb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-check" /></template>
