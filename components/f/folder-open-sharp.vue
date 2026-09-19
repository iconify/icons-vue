<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbt64hbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rbt64hbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:folder-open-sharp" /></template>
