<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkud4olzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mkud4olzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:commitizen" /></template>
