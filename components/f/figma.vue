<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmunmqb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vmunmqb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:figma" /></template>
