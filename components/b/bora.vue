<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1e2f7tko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r1e2f7tko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bora" /></template>
