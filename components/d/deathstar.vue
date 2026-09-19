<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px_p7rlgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="px_p7rlgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:deathstar" /></template>
