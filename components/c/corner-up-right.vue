<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bul6qpb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bul6qpb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:corner-up-right" /></template>
