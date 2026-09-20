<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au1r8v_ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au1r8v_ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-check" /></template>
