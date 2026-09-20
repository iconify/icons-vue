<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go6lj-7ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="go6lj-7ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:image" /></template>
