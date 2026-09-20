<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooetkb5ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3.5,"top":-1};
const content = `<path class="ooetkb5ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:leaf" /></template>
