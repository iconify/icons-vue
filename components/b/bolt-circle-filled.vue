<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m899ykb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m899ykb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bolt-circle-filled" /></template>
