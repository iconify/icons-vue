<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bchngm2td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="bchngm2td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:delete-left" /></template>
