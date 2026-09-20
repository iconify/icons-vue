<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_1ednbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v_1ednbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:cross-2" /></template>
