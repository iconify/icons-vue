<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4amp7bme.css';
import '../../css/n/nnh_4z2za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4amp7bme"/><path class="nnh_4z2za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:external-link" /></template>
