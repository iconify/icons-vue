<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy6c65bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy6c65bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:building-complex" /></template>
