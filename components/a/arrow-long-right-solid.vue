<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0axwpbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o0axwpbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-long-right-solid" /></template>
