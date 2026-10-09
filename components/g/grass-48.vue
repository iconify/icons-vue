<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwrb__blp.css';
import '../../css/m/m_hycyb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pwrb__blp"/><path class="m_hycyb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grass-48" /></template>
