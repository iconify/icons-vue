<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeboxqi-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zeboxqi-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:expand-outline" /></template>
