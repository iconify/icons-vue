<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwxxpw3nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwxxpw3nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:beer-alt-filled" /></template>
