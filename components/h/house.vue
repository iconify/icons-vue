<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j75tnrydv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j75tnrydv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:house" /></template>
