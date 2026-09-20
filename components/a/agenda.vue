<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6odmw4gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="y6odmw4gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:agenda" /></template>
