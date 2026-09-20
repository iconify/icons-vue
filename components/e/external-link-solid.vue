<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu1ht9fgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu1ht9fgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:external-link-solid" /></template>
