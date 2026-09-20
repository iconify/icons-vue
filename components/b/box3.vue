<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmis2f9is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmis2f9is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:box3" /></template>
