<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur-8hrb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ur-8hrb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:alert-fill-16" /></template>
