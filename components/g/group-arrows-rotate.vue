<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvv4pgb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nvv4pgb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:group-arrows-rotate" /></template>
