<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsecetb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="vsecetb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:broom-ball" /></template>
