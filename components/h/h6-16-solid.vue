<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp33byh8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kp33byh8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h6-16-solid" /></template>
