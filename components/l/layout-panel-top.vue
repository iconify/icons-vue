<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3jqvu3ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3jqvu3ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:layout-panel-top" /></template>
