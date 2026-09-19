<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l73w39bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l73w39bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:atom" /></template>
