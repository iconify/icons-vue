<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/difapm_qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="difapm_qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bulb" /></template>
