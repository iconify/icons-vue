<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-fc0ocqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary x-fc0ocqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-up-duotone" /></template>
