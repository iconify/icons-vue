<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myqtwccjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myqtwccjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:label-off" /></template>
