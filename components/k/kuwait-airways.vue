<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9g34x91z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9g34x91z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:kuwait-airways" /></template>
