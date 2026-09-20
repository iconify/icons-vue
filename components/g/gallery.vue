<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb40d305w.css';
import '../../css/y/y850ku1de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="mb40d305w"/><path class="y850ku1de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:gallery" /></template>
