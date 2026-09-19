<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h60l_bblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":960};
const content = `<path class="h60l_bblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:colocation" /></template>
