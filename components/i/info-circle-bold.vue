<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow8rh0bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ow8rh0bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:info-circle-bold" /></template>
