<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfcmei0vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dfcmei0vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:landline" /></template>
