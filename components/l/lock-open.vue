<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvif2zbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvif2zbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:lock-open" /></template>
