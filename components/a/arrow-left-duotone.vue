<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8_ijmbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary x8_ijmbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-left-duotone" /></template>
