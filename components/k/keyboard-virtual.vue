<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsh_3cs_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="dsh_3cs_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:keyboard-virtual" /></template>
