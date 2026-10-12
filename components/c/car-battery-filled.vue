<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywj5a93ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ywj5a93ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:car-battery-filled" /></template>
