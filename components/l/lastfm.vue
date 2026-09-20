<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkuqhvbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zkuqhvbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:lastfm" /></template>
