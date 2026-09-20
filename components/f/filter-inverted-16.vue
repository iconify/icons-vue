<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myjn58bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="myjn58bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:filter-inverted-16" /></template>
