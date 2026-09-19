<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjvv51b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sjvv51b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:flag" /></template>
