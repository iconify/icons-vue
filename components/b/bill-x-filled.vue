<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p56-9rbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p56-9rbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bill-x-filled" /></template>
