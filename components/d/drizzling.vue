<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqv79xbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qqv79xbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:drizzling" /></template>
