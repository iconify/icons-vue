<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzcjc9-6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yzcjc9-6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:disable-filled" /></template>
