<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s28o16g0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s28o16g0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cherryalt" /></template>
