<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v49-fjbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v49-fjbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-upwork" /></template>
