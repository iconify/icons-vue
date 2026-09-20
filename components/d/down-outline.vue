<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neqan3d7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="neqan3d7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:down-outline" /></template>
