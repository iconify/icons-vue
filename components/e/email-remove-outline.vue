<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkqamrqjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkqamrqjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-remove-outline" /></template>
