<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf_q4tbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf_q4tbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-pen-outline" /></template>
