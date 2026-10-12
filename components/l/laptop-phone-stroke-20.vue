<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn2sbbcpi.css';
import '../../css/a/aevwtdbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kn2sbbcpi"/><path class="aevwtdbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:laptop-phone-stroke-20" /></template>
