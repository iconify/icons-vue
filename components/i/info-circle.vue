<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thysx9bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thysx9bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:info-circle" /></template>
