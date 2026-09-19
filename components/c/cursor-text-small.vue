<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz5obbc_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="bz5obbc_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cursor-text-small" /></template>
