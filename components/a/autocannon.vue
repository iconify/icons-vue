<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvln8zfdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvln8zfdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:autocannon" /></template>
