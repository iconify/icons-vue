<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o38uoabjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o38uoabjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-grin-beam" /></template>
