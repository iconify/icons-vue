<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-wavr19y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-wavr19y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:comment-alert" /></template>
