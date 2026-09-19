<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lky_h52fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lky_h52fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:magnet" /></template>
