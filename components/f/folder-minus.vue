<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjfd3oc5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gjfd3oc5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:folder-minus" /></template>
