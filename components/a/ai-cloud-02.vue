<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l00k7ibfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l00k7ibfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-cloud-02" /></template>
