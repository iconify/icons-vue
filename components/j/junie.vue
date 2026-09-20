<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvc3yybml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvc3yybml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:junie" /></template>
