<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_o4u3b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_o4u3b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-ps-2014-open" /></template>
