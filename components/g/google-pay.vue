<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x44d7jblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="x44d7jblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:google-pay" /></template>
