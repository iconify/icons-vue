<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxswv9z9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fxswv9z9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:earth" /></template>
