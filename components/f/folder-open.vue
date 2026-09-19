<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfv_e4gpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="jfv_e4gpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:folder-open" /></template>
