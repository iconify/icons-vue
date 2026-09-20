<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr3gh3_tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gr3gh3_tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-with-peso" /></template>
