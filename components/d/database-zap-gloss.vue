<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmx0n_bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmx0n_bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:database-zap-gloss" /></template>
