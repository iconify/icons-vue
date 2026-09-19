<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8je3wbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1472};
const content = `<path class="d8je3wbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:handshake-o" /></template>
