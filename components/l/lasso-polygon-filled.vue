<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq_tio5rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq_tio5rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lasso-polygon-filled" /></template>
