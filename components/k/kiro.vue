<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3rsgcczs.css';
import '../../css/g/ghc79-30g.css';
import '../../css/l/lxc3j5b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="e3rsgcczs"/><path class="ghc79-30g"/><path class="lxc3j5b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kiro" /></template>
