<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emhpwub6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="emhpwub6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chevron-down-12" /></template>
