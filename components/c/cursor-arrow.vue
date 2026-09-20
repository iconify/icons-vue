<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyd-i4gvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyd-i4gvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cursor-arrow" /></template>
