<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrqlcd2rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrqlcd2rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:compass" /></template>
