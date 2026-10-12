<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v1vtpvbwr.css';
import '../../css/p/p395msbuh.css';
import '../../css/e/emg88iban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v1vtpvbwr"/><path class="p395msbuh"/><path class="emg88iban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bookmark-x-duotone" /></template>
