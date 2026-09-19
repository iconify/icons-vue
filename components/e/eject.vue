<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq4qg5b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1568,"height":1312};
const content = `<path class="bq4qg5b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:eject" /></template>
