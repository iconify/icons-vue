<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is5b7bcod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="is5b7bcod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:key-alt-fill" /></template>
