<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te8r7xbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te8r7xbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-three-quarter-fill" /></template>
