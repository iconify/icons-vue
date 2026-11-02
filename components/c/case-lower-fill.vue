<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcas9bc8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcas9bc8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:case-lower-fill" /></template>
