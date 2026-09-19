<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmir8hivb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":1024};
const content = `<path class="dmir8hivb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:keyhole" /></template>
