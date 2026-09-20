<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzo9mcduf.css';
import '../../css/n/nguoz603s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vzo9mcduf"/><path clip-rule="evenodd" class="nguoz603s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:computer-solid" /></template>
