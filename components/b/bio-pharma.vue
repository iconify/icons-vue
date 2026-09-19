<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf4amccmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gf4amccmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bio-pharma" /></template>
