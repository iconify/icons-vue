<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9vd6sbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9vd6sbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:bold-fill" /></template>
