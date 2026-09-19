<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezaos2o-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ezaos2o-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:folder-minus" /></template>
