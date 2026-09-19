<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4boktinr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4boktinr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:boat-filled" /></template>
