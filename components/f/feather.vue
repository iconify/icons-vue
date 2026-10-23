<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojh5zlf0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojh5zlf0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:feather" /></template>
