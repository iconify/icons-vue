<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajktiebca.css';
import '../../css/y/yox6r2bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ajktiebca"/><path class="yox6r2bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:binoculars-20" /></template>
