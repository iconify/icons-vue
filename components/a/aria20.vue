<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-f8m-b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-f8m-b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:aria20" /></template>
