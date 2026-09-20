<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aygw_60rm.css';
import '../../css/h/h09tvusar.css';
import '../../css/q/qntnbrb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aygw_60rm"/><path class="h09tvusar"/><path clip-rule="evenodd" class="qntnbrb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifer-bug-bold-duotone" /></template>
