<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmt67jnfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hmt67jnfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:kerb-lowered" /></template>
