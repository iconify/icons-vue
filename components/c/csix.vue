<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sycrcilzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sycrcilzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:csix" /></template>
