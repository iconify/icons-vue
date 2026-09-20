<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcre-4bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcre-4bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:analogue" /></template>
