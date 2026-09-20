<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytcirkb0g.css';
import '../../css/n/nctt2tb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytcirkb0g"/><path class="nctt2tb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-arrow-down-light" /></template>
