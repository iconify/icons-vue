<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy0ajee7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jy0ajee7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dollar2-filled" /></template>
