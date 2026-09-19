<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5nzycb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5nzycb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrows-h-alt" /></template>
