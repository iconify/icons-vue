<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fphb3weuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fphb3weuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:candy-solid" /></template>
