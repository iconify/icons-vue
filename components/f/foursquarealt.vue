<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv1_o64lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="jv1_o64lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:foursquarealt" /></template>
