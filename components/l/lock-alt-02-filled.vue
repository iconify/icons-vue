<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1c3_upcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1c3_upcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lock-alt-02-filled" /></template>
