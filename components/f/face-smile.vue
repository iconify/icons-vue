<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3wc6b4ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t3wc6b4ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-smile" /></template>
