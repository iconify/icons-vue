<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr1u8et0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="pr1u8et0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hands-wash" /></template>
