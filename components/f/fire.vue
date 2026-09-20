<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-z1_8y-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a-z1_8y-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:fire" /></template>
