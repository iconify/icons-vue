<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th_86r0cc.css';
import '../../css/k/k0mh91bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary th_86r0cc"/><path class="k0mh91bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-saved-objects" /></template>
