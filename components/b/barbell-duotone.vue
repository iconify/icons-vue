<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnp4-d4ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vnp4-d4ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:barbell-duotone" /></template>
