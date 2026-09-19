<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3zgf-b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r3zgf-b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:hand-wash" /></template>
