<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoo1b6bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qoo1b6bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:coffeescript" /></template>
