<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffcmlycim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ffcmlycim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bag-add-sharp" /></template>
