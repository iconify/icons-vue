<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz3575bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="nz3575bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:cog-f" /></template>
