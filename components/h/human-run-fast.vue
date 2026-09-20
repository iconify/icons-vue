<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oby2hmzeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oby2hmzeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-run-fast" /></template>
