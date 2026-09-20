<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywpgpbbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ywpgpbbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:hourglass-24" /></template>
