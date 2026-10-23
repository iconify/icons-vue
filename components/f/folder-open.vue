<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv7h3ib2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv7h3ib2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:folder-open" /></template>
