<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qww11omoa.css';
import '../../css/m/mhvhrv90s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qww11omoa"/><path class="mhvhrv90s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:circle-dot" /></template>
