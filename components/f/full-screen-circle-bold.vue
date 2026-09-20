<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s940n5tlu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s940n5tlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:full-screen-circle-bold" /></template>
