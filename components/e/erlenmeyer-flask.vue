<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlktqpbzo.css';
import '../../css/k/kif_tcbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mlktqpbzo"/><path class="kif_tcbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:erlenmeyer-flask" /></template>
