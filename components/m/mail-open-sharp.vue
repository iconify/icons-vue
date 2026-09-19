<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-1cb3qmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w-1cb3qmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:mail-open-sharp" /></template>
