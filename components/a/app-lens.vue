<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttck2cbln.css';
import '../../css/g/gd-53hb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary ttck2cbln"/><path class="gd-53hb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-lens" /></template>
