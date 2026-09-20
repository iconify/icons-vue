<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pha2xxb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pha2xxb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:body-shape2" /></template>
