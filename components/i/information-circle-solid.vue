<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr-61bb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jr-61bb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:information-circle-solid" /></template>
