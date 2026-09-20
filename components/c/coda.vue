<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzsd2gbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzsd2gbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:coda" /></template>
