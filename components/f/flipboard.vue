<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-x2a3rsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-x2a3rsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:flipboard" /></template>
