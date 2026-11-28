<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve8q_8xia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve8q_8xia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:exclude-solid" /></template>
