<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai7j36v6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ai7j36v6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:clock" /></template>
