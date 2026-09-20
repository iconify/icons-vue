<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se28wqbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="se28wqbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:exclamation-small-solid" /></template>
