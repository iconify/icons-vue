<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj8w6lbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jj8w6lbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:humhub-light" /></template>
