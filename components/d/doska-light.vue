<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8xl3h-3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b8xl3h-3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:doska-light" /></template>
