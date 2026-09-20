<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edmo9b0vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="edmo9b0vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:humhub-dark" /></template>
