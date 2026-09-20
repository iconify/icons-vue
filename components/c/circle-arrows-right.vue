<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyw5h7vrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vyw5h7vrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrows-right" /></template>
