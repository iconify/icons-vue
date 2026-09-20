<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cajv2epqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cajv2epqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lock" /></template>
