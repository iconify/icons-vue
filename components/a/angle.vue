<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr50xn6_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pr50xn6_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:angle" /></template>
