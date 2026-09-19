<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5kq0zb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5kq0zb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-wineglass" /></template>
