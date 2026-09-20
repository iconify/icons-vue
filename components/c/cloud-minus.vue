<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6lkjeh9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p6lkjeh9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-minus" /></template>
