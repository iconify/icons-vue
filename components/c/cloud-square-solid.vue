<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar94a1r8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ar94a1r8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cloud-square-solid" /></template>
