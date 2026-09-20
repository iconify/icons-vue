<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnk53dbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnk53dbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:javascript" /></template>
