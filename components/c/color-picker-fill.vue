<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5riosbee.css';
import '../../css/e/egqmiqysx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5riosbee"/><path class="egqmiqysx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:color-picker-fill" /></template>
