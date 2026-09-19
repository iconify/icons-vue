<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/purrn9t8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="purrn9t8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:address-card" /></template>
