<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnfctchuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnfctchuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:edit-pencil-line-01" /></template>
