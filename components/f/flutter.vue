<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pogpn0byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pogpn0byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:flutter" /></template>
