<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udfbpbc1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udfbpbc1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:beats" /></template>
