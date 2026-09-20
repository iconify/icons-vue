<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h80_2pb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h80_2pb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:gallery-remix" /></template>
