<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beosw2bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beosw2bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:graph-star" /></template>
