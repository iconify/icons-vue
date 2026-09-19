<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eajbiob3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eajbiob3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:facebook2" /></template>
