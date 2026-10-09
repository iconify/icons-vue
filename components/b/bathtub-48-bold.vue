<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8pzxccdr.css';
import '../../css/r/rinqinbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y8pzxccdr"/><path class="rinqinbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bathtub-48-bold" /></template>
