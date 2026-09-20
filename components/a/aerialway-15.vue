<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaodrq99u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oaodrq99u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:aerialway-15" /></template>
