<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_p4ewb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="o_p4ewb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:library" /></template>
