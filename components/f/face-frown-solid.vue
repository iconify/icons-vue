<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cktourb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cktourb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:face-frown-solid" /></template>
