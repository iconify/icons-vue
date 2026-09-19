<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gog_lij3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="gog_lij3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:language" /></template>
