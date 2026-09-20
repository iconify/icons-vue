<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7xr77kna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7xr77kna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:lock-muted-line" /></template>
