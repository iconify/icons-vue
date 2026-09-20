<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7ijt4bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ijt4bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:grid" /></template>
