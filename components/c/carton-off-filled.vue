<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqu_dzbcq.css';
import '../../css/d/dvq72viog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bqu_dzbcq"/><path class="dvq72viog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:carton-off-filled" /></template>
