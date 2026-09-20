<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvhu34bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xvhu34bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:grid-big-o" /></template>
