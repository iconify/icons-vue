<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6u2ktsbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6u2ktsbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:location" /></template>
