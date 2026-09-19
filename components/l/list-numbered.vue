<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9jy5tr7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9jy5tr7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:list-numbered" /></template>
