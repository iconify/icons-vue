<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyeh7w0zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jyeh7w0zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:close-circle-fill" /></template>
