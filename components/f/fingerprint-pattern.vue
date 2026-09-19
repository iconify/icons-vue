<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3ba6bcos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3ba6bcos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:fingerprint-pattern" /></template>
