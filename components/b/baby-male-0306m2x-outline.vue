<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi6i5jb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mi6i5jb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:baby-male-0306m2x-outline" /></template>
