<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciciw1u9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ciciw1u9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:flag-alt" /></template>
