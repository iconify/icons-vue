<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifpq7ebym.css';
import '../../css/u/un-gg2bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ifpq7ebym"/><path class="un-gg2bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-navigate-outline" /></template>
