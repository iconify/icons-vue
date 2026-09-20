<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emr3p-0fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emr3p-0fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-sidebar-right-expand-filled" /></template>
