<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lipx2eb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lipx2eb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gitlab" /></template>
