<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5-6mmbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="m5-6mmbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bold-solid" /></template>
