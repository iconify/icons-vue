<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk3iaib_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tk3iaib_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:gatsbyjs-outline" /></template>
