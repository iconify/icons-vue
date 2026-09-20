<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf7mz5b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cf7mz5b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-minus-sharp-fill" /></template>
