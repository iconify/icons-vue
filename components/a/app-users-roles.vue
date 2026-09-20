<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa312fb4p.css';
import '../../css/f/fl2n-_b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oa312fb4p"/><path class="fl2n-_b6d ouiIcon__fillSecondary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-users-roles" /></template>
