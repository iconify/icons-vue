<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if_2kzbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="if_2kzbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:disability-cane-1" /></template>
