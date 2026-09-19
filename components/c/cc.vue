<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba9o2nfex.css';
import '../../css/b/br6jib3-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ba9o2nfex"/><path class="br6jib3-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:cc" /></template>
