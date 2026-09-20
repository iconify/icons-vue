<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4-ziybhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a4-ziybhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart3-filled" /></template>
