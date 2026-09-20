<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plumexbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plumexbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cut-1" /></template>
