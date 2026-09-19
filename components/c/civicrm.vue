<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4bmut06u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z4bmut06u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:civicrm" /></template>
