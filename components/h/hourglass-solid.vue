<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zchwa-b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zchwa-b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:hourglass-solid" /></template>
