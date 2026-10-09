<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbu-t6btd.css';
import '../../css/m/mzlhdmbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kbu-t6btd"/><path class="mzlhdmbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-left-square-48-bold" /></template>
