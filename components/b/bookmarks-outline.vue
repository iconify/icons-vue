<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob6fqnbja.css';
import '../../css/u/u0bpkj-iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ob6fqnbja"/><path class="u0bpkj-iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bookmarks-outline" /></template>
