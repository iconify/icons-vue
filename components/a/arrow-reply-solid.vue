<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0yu0obka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0yu0obka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-reply-solid" /></template>
