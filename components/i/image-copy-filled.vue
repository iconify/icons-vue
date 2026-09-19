<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkvsifb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zkvsifb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:image-copy-filled" /></template>
