<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmyu4uhbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gmyu4uhbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag3" /></template>
