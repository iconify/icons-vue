<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnsz9xlwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnsz9xlwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-flame" /></template>
