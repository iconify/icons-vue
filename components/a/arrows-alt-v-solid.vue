<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8chywiab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d8chywiab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:arrows-alt-v-solid" /></template>
