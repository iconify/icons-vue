<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7wtl-18m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v7wtl-18m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:building-fill" /></template>
