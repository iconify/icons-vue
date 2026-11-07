<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvxlsjb-h.css';
import '../../css/v/vl2tm1mdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvxlsjb-h"/><path clip-rule="evenodd" class="vl2tm1mdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-check-bold" /></template>
