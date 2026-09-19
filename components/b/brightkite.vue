<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffu9thy4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":488};
const content = `<path class="ffu9thy4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:brightkite" /></template>
