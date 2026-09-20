<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py3-xbc6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py3-xbc6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:caret-right-filled" /></template>
