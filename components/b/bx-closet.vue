<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw96en5um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw96en5um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-closet" /></template>
