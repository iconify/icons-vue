<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aets0ymif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aets0ymif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge-percent" /></template>
