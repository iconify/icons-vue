<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqq0l5bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gqq0l5bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:circle-user" /></template>
