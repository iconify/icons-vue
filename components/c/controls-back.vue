<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovv0cbb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ovv0cbb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:controls-back" /></template>
