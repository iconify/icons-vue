<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmcya3l1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmcya3l1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gho" /></template>
