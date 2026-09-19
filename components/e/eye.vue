<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltn94ccoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ltn94ccoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:eye" /></template>
