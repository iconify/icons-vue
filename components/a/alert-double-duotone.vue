<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh-7v-qvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh-7v-qvz primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:alert-double-duotone" /></template>
