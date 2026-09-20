<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbigfv4ml.css';
import '../../css/b/b7y_ypb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pbigfv4ml"/><path class="b7y_ypb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-refresh" /></template>
