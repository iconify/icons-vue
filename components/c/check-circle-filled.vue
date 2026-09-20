<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzv9idc7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tzv9idc7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:check-circle-filled" /></template>
