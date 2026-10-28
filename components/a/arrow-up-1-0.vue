<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op3lkbbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op3lkbbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-1-0" /></template>
