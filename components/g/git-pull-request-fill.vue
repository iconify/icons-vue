<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inxrk9m7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inxrk9m7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-pull-request-fill" /></template>
