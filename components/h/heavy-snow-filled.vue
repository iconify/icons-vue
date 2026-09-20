<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-he_lcqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a-he_lcqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:heavy-snow-filled" /></template>
