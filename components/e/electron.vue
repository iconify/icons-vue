<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnxad5b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":474,"height":512};
const content = `<path class="jnxad5b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:electron" /></template>
