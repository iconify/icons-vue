<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fezzo6f2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="fezzo6f2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cat" /></template>
