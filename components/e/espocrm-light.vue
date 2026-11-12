<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtnz7f3pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jtnz7f3pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:espocrm-light" /></template>
