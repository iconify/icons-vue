<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avezc7byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="avezc7byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-double-20" /></template>
