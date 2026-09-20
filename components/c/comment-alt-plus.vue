<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl0vbpbky.css';
import '../../css/x/xq0giqbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl0vbpbky"/><path class="xq0giqbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:comment-alt-plus" /></template>
