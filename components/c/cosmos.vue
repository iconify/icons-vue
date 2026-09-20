<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9g0sacjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x9g0sacjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cosmos" /></template>
