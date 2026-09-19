<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmeko76qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nmeko76qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:labview-wordmark" /></template>
