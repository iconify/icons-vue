<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnw1z9bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnw1z9bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:database-2-fill" /></template>
