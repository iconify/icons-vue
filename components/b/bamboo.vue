<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx2p4cofy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dx2p4cofy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:bamboo" /></template>
