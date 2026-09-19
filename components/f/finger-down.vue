<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6r3x7qvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6r3x7qvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-down" /></template>
