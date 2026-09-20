<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqii8ob8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kqii8ob8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:link-circle-filled" /></template>
