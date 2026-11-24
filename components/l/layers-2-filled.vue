<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db1241bah.css';
import '../../css/l/l_9-3eagj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db1241bah"/><path class="l_9-3eagj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layers-2-filled" /></template>
