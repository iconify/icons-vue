<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfjl1qd8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":704};
const content = `<path class="sfjl1qd8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fedora" /></template>
