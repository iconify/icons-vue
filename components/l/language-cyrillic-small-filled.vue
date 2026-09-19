<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge4bctbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ge4bctbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-cyrillic-small-filled" /></template>
