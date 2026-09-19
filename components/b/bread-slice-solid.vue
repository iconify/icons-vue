<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-eam-cmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-eam-cmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bread-slice-solid" /></template>
