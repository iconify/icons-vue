<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncm8dqb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncm8dqb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:layout-up-fill" /></template>
