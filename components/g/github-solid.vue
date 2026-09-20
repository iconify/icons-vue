<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdy6r9b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdy6r9b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:github-solid" /></template>
