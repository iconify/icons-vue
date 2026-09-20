<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c88et_bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c88et_bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-up-left-circle-fill" /></template>
