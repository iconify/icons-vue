<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzkwg2b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzkwg2b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:focus-auto" /></template>
