<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxr5i9bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rxr5i9bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:envelope" /></template>
