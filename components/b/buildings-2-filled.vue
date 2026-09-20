<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2tbuyb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x2tbuyb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:buildings-2-filled" /></template>
