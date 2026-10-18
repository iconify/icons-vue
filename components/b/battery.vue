<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_5he8bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_5he8bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:battery" /></template>
