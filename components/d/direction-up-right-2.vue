<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptn6lmbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptn6lmbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:direction-up-right-2" /></template>
