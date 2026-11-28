<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifiw-ct-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifiw-ct-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:burger" /></template>
