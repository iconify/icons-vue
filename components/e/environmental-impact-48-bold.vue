<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwgv7ib-v.css';
import '../../css/i/is5lj6bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jwgv7ib-v"/><path class="is5lj6bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:environmental-impact-48-bold" /></template>
