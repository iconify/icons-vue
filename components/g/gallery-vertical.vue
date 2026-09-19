<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssn1mkbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssn1mkbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gallery-vertical" /></template>
