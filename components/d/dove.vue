<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvcs251if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gvcs251if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dove" /></template>
