<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0hjje8ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l0hjje8ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:down-solid" /></template>
