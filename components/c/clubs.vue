<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lki5-vbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lki5-vbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clubs" /></template>
