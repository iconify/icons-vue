<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm2leab2g.css';
import '../../css/y/yg7y-7bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pm2leab2g"/><path class="yg7y-7bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caliper-48-bold" /></template>
