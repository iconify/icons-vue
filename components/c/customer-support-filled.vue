<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo1nx8fzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zo1nx8fzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:customer-support-filled" /></template>
