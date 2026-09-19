<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-cz3x_bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="x-cz3x_bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dolly" /></template>
