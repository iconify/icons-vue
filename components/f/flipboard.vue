<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9k7zhbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9k7zhbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:flipboard" /></template>
