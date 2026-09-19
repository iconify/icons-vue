<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zntl3sptn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zntl3sptn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:departement" /></template>
