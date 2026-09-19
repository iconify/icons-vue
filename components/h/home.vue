<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soz8xib7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="soz8xib7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:home" /></template>
