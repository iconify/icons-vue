<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbu-t6btd.css';
import '../../css/q/ql3mu_b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kbu-t6btd"/><path class="ql3mu_b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-down-square-48-bold" /></template>
