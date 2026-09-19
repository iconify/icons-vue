<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgj9wvwbi.css';
import '../../css/t/tvkysof6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgj9wvwbi"/><path class="tvkysof6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-log-in-circle" /></template>
