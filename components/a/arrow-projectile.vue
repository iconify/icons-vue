<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or5jkcb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="or5jkcb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-projectile" /></template>
