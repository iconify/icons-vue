<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_p1nbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca_p1nbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clear-all-fill" /></template>
