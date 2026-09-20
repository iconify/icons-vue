<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhxy26blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nhxy26blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bulb-off-solid" /></template>
