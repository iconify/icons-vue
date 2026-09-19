<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy42re5xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy42re5xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:git-branch" /></template>
