<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdv_x32nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mdv_x32nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-fill" /></template>
