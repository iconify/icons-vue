<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoufhkb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoufhkb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:check-square-fill" /></template>
