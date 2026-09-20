<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_momnr0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_momnr0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-2-spark" /></template>
