<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf2-xfbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf2-xfbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:code" /></template>
