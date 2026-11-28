<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_fizovni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v_fizovni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrows-left-right-duotone" /></template>
