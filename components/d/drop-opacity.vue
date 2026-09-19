<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csjj4tjvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="csjj4tjvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:drop-opacity" /></template>
