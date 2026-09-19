<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjr-4xaxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gjr-4xaxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:blood-drop" /></template>
