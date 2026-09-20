<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aggim0kia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aggim0kia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:clyp" /></template>
