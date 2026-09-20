<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkgib055v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lkgib055v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filesync-dark" /></template>
