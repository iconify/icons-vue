<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlcn8qbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hlcn8qbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-shopping-logo-solid" /></template>
