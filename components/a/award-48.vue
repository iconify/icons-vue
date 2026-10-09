<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7kugr3av.css';
import '../../css/b/bqdx-xuwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b7kugr3av"/><path class="bqdx-xuwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:award-48" /></template>
