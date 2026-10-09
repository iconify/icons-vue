<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bojscnbzb.css';
import '../../css/u/uj137zbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bojscnbzb"/><path class="uj137zbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:glasses-48-bold" /></template>
