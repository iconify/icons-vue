<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqcdx_jqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uqcdx_jqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-question-sharp-fill" /></template>
