<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb1jiicvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lb1jiicvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:electronic" /></template>
