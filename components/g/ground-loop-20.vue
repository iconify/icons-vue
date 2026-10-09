<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-tex-1tc.css';
import '../../css/v/vzrht_bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v-tex-1tc"/><path class="vzrht_bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ground-loop-20" /></template>
