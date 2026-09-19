<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu8f02jqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xu8f02jqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:face-sad" /></template>
