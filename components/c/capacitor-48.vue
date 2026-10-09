<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bybnubbfi.css';
import '../../css/b/bc05qzspk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bybnubbfi"/><path class="bc05qzspk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:capacitor-48" /></template>
