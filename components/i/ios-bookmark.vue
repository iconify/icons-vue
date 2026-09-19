<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmejnq0yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dmejnq0yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-bookmark" /></template>
