<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn6xy5bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kn6xy5bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:bank" /></template>
