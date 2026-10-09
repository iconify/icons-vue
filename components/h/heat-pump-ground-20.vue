<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2cai_bki.css';
import '../../css/b/bq2hwibav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b2cai_bki"/><path clip-rule="evenodd" class="bq2hwibav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-ground-20" /></template>
