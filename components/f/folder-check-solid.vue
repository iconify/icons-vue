<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd816bv3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd816bv3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-check-solid" /></template>
