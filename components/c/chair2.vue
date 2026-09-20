<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbd70xz5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nbd70xz5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chair2" /></template>
