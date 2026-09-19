<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei2152blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":372,"height":512};
const content = `<path class="ei2152blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:augeas" /></template>
