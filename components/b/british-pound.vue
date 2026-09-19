<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwseektoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gwseektoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:british-pound" /></template>
