<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdasiyb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fdasiyb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-right-square-filled" /></template>
