<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk9ls1b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kk9ls1b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:c-solid" /></template>
