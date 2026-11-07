<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kubz8lo_c.css';
import '../../css/e/elic3l99c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kubz8lo_c"/><path class="elic3l99c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbell-bold-duotone" /></template>
