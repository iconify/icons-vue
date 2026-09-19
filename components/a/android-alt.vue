<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqzh37bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oqzh37bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:android-alt" /></template>
