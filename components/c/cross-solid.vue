<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o204y9n4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o204y9n4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cross-solid" /></template>
