<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qflxi5six.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qflxi5six"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:link-sharp" /></template>
