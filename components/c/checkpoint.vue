<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-jfigb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o-jfigb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:checkpoint" /></template>
