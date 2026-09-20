<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq_9v787t.css';
import '../../css/v/vp-9qc54u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eq_9v787t"/><path class="vp-9qc54u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:ambulance" /></template>
