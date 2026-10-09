<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9xk66b5z.css';
import '../../css/k/k8q9q9bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9xk66b5z"/><path class="k8q9q9bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:laundry-basket-48-bold" /></template>
