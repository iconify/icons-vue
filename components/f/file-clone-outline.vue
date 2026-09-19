<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di935-bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di935-bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-clone-outline" /></template>
