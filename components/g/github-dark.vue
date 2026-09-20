<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hajm5gbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hajm5gbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:github-dark" /></template>
