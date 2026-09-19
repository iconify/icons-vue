<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvk93ab1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nvk93ab1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-checkmark" /></template>
