<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf-3i8bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tf-3i8bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-up" /></template>
