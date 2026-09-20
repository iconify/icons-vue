<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfx94ekeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfx94ekeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:controller" /></template>
