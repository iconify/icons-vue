<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-5tw0hwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-5tw0hwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:label-multiple" /></template>
