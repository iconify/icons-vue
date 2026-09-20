<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el1eu57nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="el1eu57nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-droplet" /></template>
