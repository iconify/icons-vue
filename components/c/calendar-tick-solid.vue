<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh8kezbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="bh8kezbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:calendar-tick-solid" /></template>
