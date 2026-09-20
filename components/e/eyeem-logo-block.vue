<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyk52k0bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyk52k0bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:eyeem-logo-block" /></template>
