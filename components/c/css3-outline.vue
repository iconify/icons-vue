<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdrpvbclv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kdrpvbclv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:css3-outline" /></template>
