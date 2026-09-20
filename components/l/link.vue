<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2m7awbvd.css';
import '../../css/g/ggfvuibun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b2m7awbvd"/><path class="ggfvuibun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:link" /></template>
