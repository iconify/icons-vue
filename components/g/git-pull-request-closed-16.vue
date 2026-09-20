<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptwnyxbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ptwnyxbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-pull-request-closed-16" /></template>
