<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d51p1bo9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d51p1bo9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flickr-fill" /></template>
