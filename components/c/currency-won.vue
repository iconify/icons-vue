<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-02zwb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-02zwb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:currency-won" /></template>
