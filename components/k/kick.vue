<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr9ingbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr9ingbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kick" /></template>
