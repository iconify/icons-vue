<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej9tf-bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej9tf-bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-minimalistic-bold" /></template>
