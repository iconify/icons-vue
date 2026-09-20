<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy88r021n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fy88r021n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoiceshelf-light" /></template>
