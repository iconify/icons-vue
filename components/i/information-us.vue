<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcjq7gb3l.css';
import '../../css/h/hgh3anbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="vcjq7gb3l"/><path class="hgh3anbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:information-us" /></template>
