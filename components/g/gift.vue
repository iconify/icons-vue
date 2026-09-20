<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujatkbcco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ujatkbcco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:gift" /></template>
