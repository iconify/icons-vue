<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dva4gabsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="dva4gabsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grin" /></template>
