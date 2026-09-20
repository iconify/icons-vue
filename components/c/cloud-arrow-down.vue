<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujwr_lkax.css';
import '../../css/h/hntribk9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujwr_lkax"/><path class="hntribk9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cloud-arrow-down" /></template>
