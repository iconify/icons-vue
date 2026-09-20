<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d10gn0bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d10gn0bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hft" /></template>
