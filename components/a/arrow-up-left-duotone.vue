<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3q-b4urp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v3q-b4urp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-left-duotone" /></template>
