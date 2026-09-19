<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3on08bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l3on08bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-git-pull-request" /></template>
