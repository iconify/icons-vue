<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov8y93bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ov8y93bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:aerospike" /></template>
