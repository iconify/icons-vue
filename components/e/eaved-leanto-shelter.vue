<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0nijscvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j0nijscvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-leanto-shelter" /></template>
