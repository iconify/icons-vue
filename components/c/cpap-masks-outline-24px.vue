<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkzggvjby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkzggvjby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cpap-masks-outline-24px" /></template>
