<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bggzpxb-r.css';
import '../../css/v/v-7fu2bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bggzpxb-r"/><path class="v-7fu2bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:composerize" /></template>
