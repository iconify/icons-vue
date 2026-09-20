<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2yt0tb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b2yt0tb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar-search" /></template>
