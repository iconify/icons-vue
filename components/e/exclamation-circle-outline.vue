<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfjex6bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gfjex6bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:exclamation-circle-outline" /></template>
