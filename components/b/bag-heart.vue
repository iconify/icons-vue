<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxrlv9bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qxrlv9bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag-heart" /></template>
