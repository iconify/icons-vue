<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnxe0jbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nnxe0jbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:chevron-right-fill" /></template>
