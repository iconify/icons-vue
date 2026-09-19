<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toxq-5b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="toxq-5b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-right-solid" /></template>
