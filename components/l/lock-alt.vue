<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq40seb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="qq40seb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:lock-alt" /></template>
