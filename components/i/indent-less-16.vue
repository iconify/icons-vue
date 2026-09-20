<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr0z36_3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fr0z36_3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:indent-less-16" /></template>
