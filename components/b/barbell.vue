<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hko1tx88j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hko1tx88j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:barbell" /></template>
