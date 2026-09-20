<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4545e9po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a4545e9po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bulb-on-solid" /></template>
