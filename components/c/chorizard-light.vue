<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eow2v3j8v.css';
import '../../css/l/lylvmeb0j.css';
import '../../css/c/cgm5haclf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eow2v3j8v"/><path class="lylvmeb0j"/><path class="cgm5haclf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chorizard-light" /></template>
