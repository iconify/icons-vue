<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl5v1rsmq.css';
import '../../css/v/v9rv_hbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hl5v1rsmq"/><path class="v9rv_hbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:key-stroke-20" /></template>
