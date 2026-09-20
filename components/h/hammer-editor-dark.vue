<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjt07rb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yjt07rb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hammer-editor-dark" /></template>
