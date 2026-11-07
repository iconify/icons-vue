<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar8y-0h1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar8y-0h1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:earth-broken" /></template>
