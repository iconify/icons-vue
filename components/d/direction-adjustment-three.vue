<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjudv46oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sjudv46oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:direction-adjustment-three" /></template>
