<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuofbk7zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xuofbk7zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:add-outline" /></template>
