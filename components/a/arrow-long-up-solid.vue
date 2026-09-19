<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq7r5obcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tq7r5obcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-long-up-solid" /></template>
