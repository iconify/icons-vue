<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3r63-bok.css';
import '../../css/x/x53871j6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k3r63-bok"/><path class="x53871j6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:coffee-bean-solid" /></template>
