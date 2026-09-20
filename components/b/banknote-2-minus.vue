<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my8yzbcwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my8yzbcwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-2-minus" /></template>
