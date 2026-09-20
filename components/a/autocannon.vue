<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrvp8ub5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrvp8ub5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:autocannon" /></template>
