<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxvehrb0j.css';
import '../../css/h/h-13c9bbf.css';
import '../../css/r/r99w2lb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oxvehrb0j"/><path class="h-13c9bbf"/><path class="r99w2lb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-codepen" /></template>
