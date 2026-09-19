<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_771mbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s_771mbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:animal-donkey-outline" /></template>
