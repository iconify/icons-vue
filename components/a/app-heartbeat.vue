<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojvj-2bxz.css';
import '../../css/g/giecwuhng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ojvj-2bxz ouiIcon__fillSecondary"/><path class="giecwuhng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-heartbeat" /></template>
