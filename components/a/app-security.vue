<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j54z2ny8a.css';
import '../../css/o/og107ss5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j54z2ny8a"/><path class="og107ss5y ouiIcon__fillSecondary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-security" /></template>
