<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8vmp6bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8vmp6bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-downward-square-line" /></template>
