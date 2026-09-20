<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1qizrb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a1qizrb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-down2" /></template>
