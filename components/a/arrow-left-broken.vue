<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-itidbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-itidbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-broken" /></template>
