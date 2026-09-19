<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn-43ri1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rn-43ri1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-storefront-16-solid" /></template>
