<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a84a1jczv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="a84a1jczv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:confirmation-number" /></template>
