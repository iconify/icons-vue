<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxn06vble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxn06vble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-bottom-right" /></template>
