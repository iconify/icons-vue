<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t59excn8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t59excn8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:floppy-disk-1" /></template>
