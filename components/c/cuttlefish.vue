<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7za0ffov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p7za0ffov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cuttlefish" /></template>
