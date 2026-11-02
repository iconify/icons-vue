<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci-c0yb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci-c0yb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gender-trans" /></template>
