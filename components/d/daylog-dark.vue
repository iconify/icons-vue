<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2ipv8b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b2ipv8b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:daylog-dark" /></template>
