<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv8ezdbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nv8ezdbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:face-smile" /></template>
