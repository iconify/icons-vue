<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6f8disse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6f8disse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-solid" /></template>
