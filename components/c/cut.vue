<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuke3kefl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="kuke3kefl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cut" /></template>
