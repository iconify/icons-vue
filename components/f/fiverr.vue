<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyd2bpchq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyd2bpchq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:fiverr" /></template>
