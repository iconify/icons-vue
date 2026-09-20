<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewf70vbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewf70vbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-2" /></template>
