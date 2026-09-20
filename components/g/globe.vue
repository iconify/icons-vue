<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab1dbfbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab1dbfbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe" /></template>
