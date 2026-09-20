<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s23tf7rzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s23tf7rzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:devbox" /></template>
