<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt1xgbbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt1xgbbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:general-motors" /></template>
