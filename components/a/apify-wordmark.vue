<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltikhp55e.css';
import '../../css/i/i4nkalbtd.css';
import '../../css/u/uykw5abjm.css';
import '../../css/g/gfprm-lkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ltikhp55e"/><path class="i4nkalbtd"/><path class="uykw5abjm"/><path class="gfprm-lkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:apify-wordmark" /></template>
