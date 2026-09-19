<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agal7ibzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="agal7ibzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:intercom" /></template>
