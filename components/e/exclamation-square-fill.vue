<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-yw3ub1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-yw3ub1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:exclamation-square-fill" /></template>
