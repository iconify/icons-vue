<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqo-cjb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lqo-cjb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:delete" /></template>
