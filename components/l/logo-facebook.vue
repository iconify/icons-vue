<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8k43r4ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v8k43r4ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-facebook" /></template>
