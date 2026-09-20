<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erv20k74w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erv20k74w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:handicapped-fill" /></template>
