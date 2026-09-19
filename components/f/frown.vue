<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o13g0ubbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="o13g0ubbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:frown" /></template>
