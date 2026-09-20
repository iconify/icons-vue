<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odmwx1c-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odmwx1c-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:aol" /></template>
