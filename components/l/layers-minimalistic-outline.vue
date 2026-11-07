<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjxww401x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cjxww401x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layers-minimalistic-outline" /></template>
