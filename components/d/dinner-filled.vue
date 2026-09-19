<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg-8bfyph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mg-8bfyph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:dinner-filled" /></template>
