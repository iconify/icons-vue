<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yew2c0sjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yew2c0sjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-mastodon" /></template>
