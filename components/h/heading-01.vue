<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da52_eirn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da52_eirn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heading-01" /></template>
