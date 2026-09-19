<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pld43v02m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pld43v02m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:hard-drive" /></template>
