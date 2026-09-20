<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt9yvqrca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pt9yvqrca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:buildings3-filled" /></template>
