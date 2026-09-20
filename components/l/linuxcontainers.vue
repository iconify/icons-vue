<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gklwl06rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gklwl06rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:linuxcontainers" /></template>
