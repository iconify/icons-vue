<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss6w1acng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss6w1acng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-mastodon" /></template>
