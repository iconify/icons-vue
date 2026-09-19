<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgcbpcb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vgcbpcb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-plus" /></template>
