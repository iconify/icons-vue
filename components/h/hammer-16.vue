<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is0lndb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="is0lndb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:hammer-16" /></template>
