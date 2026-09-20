<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a82ao3b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a82ao3b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:logchef-dark" /></template>
