<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_1fj88zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="p_1fj88zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:csv-solid" /></template>
