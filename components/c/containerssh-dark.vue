<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb5bgx25v.css';
import '../../css/a/az6xitzef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wb5bgx25v"/><path class="az6xitzef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:containerssh-dark" /></template>
