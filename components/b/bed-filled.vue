<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p24z8pbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p24z8pbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:bed-filled" /></template>
