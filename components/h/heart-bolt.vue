<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zozeas57z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zozeas57z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heart-bolt" /></template>
