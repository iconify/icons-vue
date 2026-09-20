<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq6_t6blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq6_t6blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lamp-slash-filled" /></template>
