<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx35p2zye.css';
import '../../css/c/cszcplbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx35p2zye"/><path class="cszcplbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:java-script" /></template>
