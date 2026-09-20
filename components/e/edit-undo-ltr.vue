<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot_dhmbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ot_dhmbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:edit-undo-ltr" /></template>
