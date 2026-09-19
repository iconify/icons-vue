<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzfce9bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":49,"height":48};
const content = `<path class="xzfce9bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:kettle" /></template>
