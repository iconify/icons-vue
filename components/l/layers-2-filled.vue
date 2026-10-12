<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqp3zebpd.css';
import '../../css/l/l_9-3eagj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqp3zebpd"/><path class="l_9-3eagj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layers-2-filled" /></template>
