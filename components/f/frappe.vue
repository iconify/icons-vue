<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6u4_b-mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6u4_b-mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:frappe" /></template>
