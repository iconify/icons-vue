<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw_k-4pjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw_k-4pjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:delta-filled" /></template>
