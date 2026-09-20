<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1g40kz8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1g40kz8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge-alert" /></template>
