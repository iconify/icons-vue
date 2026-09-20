<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkv30x99a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gkv30x99a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:diamond-solid" /></template>
