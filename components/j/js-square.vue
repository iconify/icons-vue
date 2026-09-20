<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a89o3fw4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a89o3fw4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:js-square" /></template>
