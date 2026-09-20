<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvj3hy0ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvj3hy0ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:link-circle3-filled" /></template>
