<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pztiz2epx.css';
import '../../css/u/ur-nm2blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pztiz2epx"/><path class="ur-nm2blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-pull-request-unlisted-16" /></template>
