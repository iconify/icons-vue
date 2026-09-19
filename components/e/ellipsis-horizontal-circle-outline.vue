<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuejpjjmz.css';
import '../../css/b/be4ff7bzh.css';
import '../../css/z/zhu4enjix.css';
import '../../css/l/lsg5j7ibl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vuejpjjmz"/><circle class="be4ff7bzh"/><circle class="zhu4enjix"/><path class="lsg5j7ibl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:ellipsis-horizontal-circle-outline" /></template>
