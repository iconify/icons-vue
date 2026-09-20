<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9v41_qpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9v41_qpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:direction-alt-3-fill" /></template>
