<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmvn587za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmvn587za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-3-bottom-right-solid" /></template>
