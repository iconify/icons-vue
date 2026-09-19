<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrcd7qbgp.css';
import '../../css/b/b8kj2gpmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="mrcd7qbgp"/><path class="b8kj2gpmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-camera" /></template>
