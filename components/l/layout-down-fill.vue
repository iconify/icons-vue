<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv26_lbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv26_lbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:layout-down-fill" /></template>
