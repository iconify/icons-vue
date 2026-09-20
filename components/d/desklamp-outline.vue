<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyyq6eeli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tyyq6eeli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:desklamp-outline" /></template>
