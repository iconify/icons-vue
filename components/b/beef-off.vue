<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofpns1bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofpns1bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:beef-off" /></template>
