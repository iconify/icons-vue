<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo4ka8j4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yo4ka8j4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lasso" /></template>
