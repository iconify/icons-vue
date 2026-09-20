<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el_v__osi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el_v__osi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lock-percent-open" /></template>
