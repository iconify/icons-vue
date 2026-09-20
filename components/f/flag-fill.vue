<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcvq68b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcvq68b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:flag-fill" /></template>
