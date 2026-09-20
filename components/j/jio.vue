<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-37ybbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-37ybbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jio" /></template>
