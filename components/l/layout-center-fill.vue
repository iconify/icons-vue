<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh3i-6oef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh3i-6oef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:layout-center-fill" /></template>
