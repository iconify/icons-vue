<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqpg69lvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqpg69lvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-add-outline" /></template>
