<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_2w7xb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="n_2w7xb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-up-from-water-pump" /></template>
