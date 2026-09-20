<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny4i4fb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny4i4fb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-broken" /></template>
