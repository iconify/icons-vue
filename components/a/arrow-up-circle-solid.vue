<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy251cc0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dy251cc0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-up-circle-solid" /></template>
