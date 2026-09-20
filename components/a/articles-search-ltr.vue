<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1___qv1l.css';
import '../../css/l/lsxdb1s3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q1___qv1l"/><path class="lsxdb1s3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:articles-search-ltr" /></template>
