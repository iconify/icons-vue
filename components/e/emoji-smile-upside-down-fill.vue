<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df6l_sv9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="df6l_sv9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:emoji-smile-upside-down-fill" /></template>
