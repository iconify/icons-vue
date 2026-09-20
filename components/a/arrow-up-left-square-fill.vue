<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx3zlefwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx3zlefwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-up-left-square-fill" /></template>
