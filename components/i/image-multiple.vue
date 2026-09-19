<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxm_c3b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxm_c3b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:image-multiple" /></template>
