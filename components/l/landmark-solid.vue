<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgierebuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgierebuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:landmark-solid" /></template>
