<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbn6zo7il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="sbn6zo7il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:convenience-store" /></template>
