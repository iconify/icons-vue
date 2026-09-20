<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6t49zkgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w6t49zkgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:closet2-filled" /></template>
