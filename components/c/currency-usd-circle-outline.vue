<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf_s62bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf_s62bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:currency-usd-circle-outline" /></template>
