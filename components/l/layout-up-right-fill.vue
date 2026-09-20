<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itx6mhbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itx6mhbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:layout-up-right-fill" /></template>
