<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlyoxob2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlyoxob2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bluesound" /></template>
