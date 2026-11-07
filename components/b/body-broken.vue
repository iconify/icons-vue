<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el3w6m6et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el3w6m6et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-broken" /></template>
