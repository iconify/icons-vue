<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rerz_fbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rerz_fbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:card-pay-fill" /></template>
