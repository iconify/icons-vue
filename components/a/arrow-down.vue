<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5w2sby7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5w2sby7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down" /></template>
