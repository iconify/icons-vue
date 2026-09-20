<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apqzseb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="apqzseb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:capsule-1" /></template>
