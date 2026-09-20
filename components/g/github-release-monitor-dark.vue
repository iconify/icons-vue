<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjn8idhbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pjn8idhbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:github-release-monitor-dark" /></template>
