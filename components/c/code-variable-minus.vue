<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlsw8r0tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlsw8r0tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:code-variable-minus" /></template>
