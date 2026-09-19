<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr8crrw1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nr8crrw1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cafe" /></template>
