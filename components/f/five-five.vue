<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4z4-ob1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y4z4-ob1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:five-five" /></template>
