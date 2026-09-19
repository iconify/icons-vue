<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yboodzbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yboodzbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:clipboard-solid" /></template>
