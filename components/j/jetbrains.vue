<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwk5x-bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jwk5x-bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:jetbrains" /></template>
