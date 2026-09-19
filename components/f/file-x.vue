<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjbpxbblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjbpxbblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-x" /></template>
