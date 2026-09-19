<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ropv3trbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ropv3trbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrows-rotate-left" /></template>
