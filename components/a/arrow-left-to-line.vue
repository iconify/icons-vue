<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hix4dmajl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hix4dmajl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-left-to-line" /></template>
