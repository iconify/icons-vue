<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyyj18bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyyj18bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ferrarinv" /></template>
