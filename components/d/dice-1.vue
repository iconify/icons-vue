<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtqzxr8te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtqzxr8te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:dice-1" /></template>
