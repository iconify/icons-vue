<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkrbc7bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jkrbc7bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:dialpad" /></template>
