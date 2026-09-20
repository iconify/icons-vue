<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/accioub1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="accioub1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:arrow-alt-circle-right" /></template>
