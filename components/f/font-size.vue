<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkub0ab9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nkub0ab9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:font-size" /></template>
