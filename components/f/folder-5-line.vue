<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiut2o5jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiut2o5jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-5-line" /></template>
