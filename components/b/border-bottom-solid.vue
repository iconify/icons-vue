<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/majnp3bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="majnp3bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-bottom-solid" /></template>
