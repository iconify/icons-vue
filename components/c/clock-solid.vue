<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i51od5bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i51od5bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:clock-solid" /></template>
