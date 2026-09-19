<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgraijbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgraijbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cog-solid" /></template>
