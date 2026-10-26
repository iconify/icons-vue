<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o38pqhu6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o38pqhu6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:acupuncture-4" /></template>
