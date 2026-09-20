<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic4bk9nie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ic4bk9nie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:battery-1-outline" /></template>
