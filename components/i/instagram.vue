<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw5pnvb2b.css';
import '../../css/c/c2wy4abda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw5pnvb2b"/><path class="c2wy4abda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:instagram" /></template>
