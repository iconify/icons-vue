<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnv8itteo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vnv8itteo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:airplane" /></template>
