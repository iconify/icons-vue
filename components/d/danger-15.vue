<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4xv51bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m4xv51bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:danger-15" /></template>
