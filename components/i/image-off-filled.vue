<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6fz4cbaf.css';
import '../../css/w/wvjpim6nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r6fz4cbaf"/><path class="wvjpim6nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:image-off-filled" /></template>
