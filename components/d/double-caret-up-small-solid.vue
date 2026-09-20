<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zon_gqbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="zon_gqbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-up-small-solid" /></template>
