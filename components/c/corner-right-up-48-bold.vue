<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liyswgvjl.css';
import '../../css/o/or_bkw-qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="liyswgvjl"/><path class="or_bkw-qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-right-up-48-bold" /></template>
