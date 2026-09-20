<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlt4macjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="rlt4macjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-renamed" /></template>
