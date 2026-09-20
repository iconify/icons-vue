<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bugd6-bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bugd6-bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:folder-down" /></template>
