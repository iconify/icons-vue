<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kruzd2qkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kruzd2qkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bull" /></template>
