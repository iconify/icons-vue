<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxjhjgbtl.css';
import '../../css/k/kcmyxgenc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxjhjgbtl"/><path class="kcmyxgenc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-3-bold-duotone" /></template>
