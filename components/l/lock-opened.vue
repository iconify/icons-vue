<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv3lvgb1x.css';
import '../../css/p/pr-lh_29u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv3lvgb1x"/><path class="pr-lh_29u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:lock-opened" /></template>
