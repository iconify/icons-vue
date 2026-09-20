<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_0lc8gzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s_0lc8gzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:magicmirror2-dark" /></template>
