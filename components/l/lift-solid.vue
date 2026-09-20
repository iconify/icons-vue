<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mih06rbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mih06rbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:lift-solid" /></template>
