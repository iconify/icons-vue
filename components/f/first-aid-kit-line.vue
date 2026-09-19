<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj7pqvbdz.css';
import '../../css/s/s0pa6pmmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="kj7pqvbdz"/><path class="s0pa6pmmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:first-aid-kit-line" /></template>
