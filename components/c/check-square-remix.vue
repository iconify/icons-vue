<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrv-p4bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jrv-p4bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:check-square-remix" /></template>
