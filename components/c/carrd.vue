<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onw3tixkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onw3tixkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:carrd" /></template>
