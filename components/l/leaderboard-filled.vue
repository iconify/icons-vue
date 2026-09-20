<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b361owb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b361owb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:leaderboard-filled" /></template>
