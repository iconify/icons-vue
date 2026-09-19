<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyopewbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tyopewbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:checkbox-sharp" /></template>
