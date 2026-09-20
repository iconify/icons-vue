<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0f-w2b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0f-w2b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:https-filled" /></template>
