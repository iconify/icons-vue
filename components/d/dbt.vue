<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agj2wabqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agj2wabqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dbt" /></template>
