<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn3ddwbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn3ddwbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dental-off" /></template>
