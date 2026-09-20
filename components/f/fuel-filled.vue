<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvm73jb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hvm73jb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fuel-filled" /></template>
