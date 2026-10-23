<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilq2v_dve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilq2v_dve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:app-window" /></template>
