<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czacm9bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="czacm9bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:calendar-solid" /></template>
