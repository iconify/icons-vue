<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxg3z72tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lxg3z72tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:git-pages-dark" /></template>
