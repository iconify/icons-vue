<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inel58btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inel58btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:diamonds-2" /></template>
