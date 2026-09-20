<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi2o-w3ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi2o-w3ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:empathize-off" /></template>
