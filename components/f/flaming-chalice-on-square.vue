<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g81wb51pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g81wb51pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flaming-chalice-on-square" /></template>
