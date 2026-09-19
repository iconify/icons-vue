<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu0undb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qu0undb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:airplane" /></template>
