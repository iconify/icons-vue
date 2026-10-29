<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsvigrbgh.css';
import '../../css/f/fc-kwxboe.css';
import '../../css/z/zxxmof9pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsvigrbgh wm-shadow"/><path class="fc-kwxboe wm-k"/><path class="wm-k zxxmof9pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:loader-circle" /></template>
