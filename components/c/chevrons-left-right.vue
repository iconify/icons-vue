<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqxap_bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqxap_bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevrons-left-right" /></template>
