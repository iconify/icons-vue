<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkr6qsb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kkr6qsb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:log-out" /></template>
