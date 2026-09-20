<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv1tmnbqm.css';
import '../../css/t/tl0tvc7vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yv1tmnbqm"/><path clip-rule="evenodd" class="tl0tvc7vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-confirm-user" /></template>
