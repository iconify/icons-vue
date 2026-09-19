<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yil8a7ebz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yil8a7ebz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-forward-sharp" /></template>
