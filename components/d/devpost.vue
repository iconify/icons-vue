<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou_ifdb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou_ifdb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:devpost" /></template>
