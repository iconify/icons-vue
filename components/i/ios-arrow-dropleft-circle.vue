<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4n8a_oym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p4n8a_oym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-dropleft-circle" /></template>
