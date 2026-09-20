<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6qek2uec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6qek2uec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-plus-logo-2-block" /></template>
