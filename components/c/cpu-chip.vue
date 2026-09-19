<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr5-lrekc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr5-lrekc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cpu-chip" /></template>
