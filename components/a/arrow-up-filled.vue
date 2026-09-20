<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0dmv8ksy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b0dmv8ksy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:arrow-up-filled" /></template>
